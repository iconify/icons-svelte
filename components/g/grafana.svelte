<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfsg-tbww.css';
import '../../css/m/mad_2hbbu.css';
import '../../css/f/fi5bwcx5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":279};
const content = `<defs><linearGradient id="SVGzNMMBeHh" x1="49.995%" x2="49.995%" y1="122.45%" y2="31.139%"><stop offset="0%" class="mfsg-tbww"/><stop offset="100%" class="mad_2hbbu"/></linearGradient></defs><path fill="url(#SVGzNMMBeHh)" class="fi5bwcx5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:grafana" {...props}></Icon>
