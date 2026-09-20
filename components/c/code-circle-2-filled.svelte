<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-c2jjncm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-c2jjncm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:code-circle-2-filled" {...props}></Icon>
