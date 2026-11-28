<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbxs4bbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbxs4bbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pull-request-check" {...props}></Icon>
