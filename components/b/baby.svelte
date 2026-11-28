<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahch_tvuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahch_tvuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:baby" {...props}></Icon>
