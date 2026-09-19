<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by7gwpbho.css';
import '../../css/p/pnb1asb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by7gwpbho duoicon-secondary-layer"/><path class="duoicon-primary-layer pnb1asb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:discount" {...props}></Icon>
