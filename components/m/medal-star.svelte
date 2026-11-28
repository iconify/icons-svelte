<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmgt9yblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmgt9yblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:medal-star" {...props}></Icon>
