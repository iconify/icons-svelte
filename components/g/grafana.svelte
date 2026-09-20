<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mad_2hbbu.css';
import '../../css/e/eoy1so5qh.css';
import '../../css/j/jpa441bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGqcchnezh" x1="256.002" x2="256.002" y1="432.036" y2="787.262" gradientTransform="translate(0 -279)" gradientUnits="userSpaceOnUse"><stop offset="0" class="mad_2hbbu"/><stop offset="1" class="eoy1so5qh"/></linearGradient><path fill="url(#SVGqcchnezh)" class="jpa441bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana" {...props}></Icon>
