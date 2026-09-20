<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxdyb9byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxdyb9byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pearson" {...props}></Icon>
