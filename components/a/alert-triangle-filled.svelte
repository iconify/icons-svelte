<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7lysgngy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7lysgngy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alert-triangle-filled" {...props}></Icon>
