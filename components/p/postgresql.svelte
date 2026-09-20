<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj_-cngib.css';
import '../../css/z/z-izombsf.css';
import '../../css/b/b9755ib4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uj_-cngib"/><path class="z-izombsf"/><path class="b9755ib4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:postgresql" {...props}></Icon>
