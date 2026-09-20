<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujj4-jdsj.css';
import '../../css/h/hbovmzbev.css';
import '../../css/u/uc21-y-ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ujj4-jdsj"/><path class="hbovmzbev"/><path class="uc21-y-ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nx-witness-dark" {...props}></Icon>
