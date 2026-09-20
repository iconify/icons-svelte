<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d28cjibda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d28cjibda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:plane-arrival-filled" {...props}></Icon>
