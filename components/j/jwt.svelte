<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6x784t-a.css';
import '../../css/z/z2lg6u2gl.css';
import '../../css/r/rj5nmqbtj.css';
import '../../css/k/k7a_rqnoj.css';
import '../../css/p/pqbp2bdrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":257};
const content = `<path class="r6x784t-a"/><path class="z2lg6u2gl"/><path class="rj5nmqbtj"/><path class="k7a_rqnoj"/><path class="pqbp2bdrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jwt" {...props}></Icon>
