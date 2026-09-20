<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq1eo_bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq1eo_bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bitcomet" {...props}></Icon>
