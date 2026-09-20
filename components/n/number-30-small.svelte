<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouue8ejct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouue8ejct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-30-small" {...props}></Icon>
