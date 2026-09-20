<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8a-spftx.css';
import '../../css/f/f--a68y4g.css';
import '../../css/g/g-vas9vud.css';
import '../../css/o/ogbi9fbdn.css';
import '../../css/a/ay8131wny.css';
import '../../css/p/pvt39jcep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="a8a-spftx"/><path class="f--a68y4g"/><path class="g-vas9vud"/><path class="ogbi9fbdn"/><circle class="ay8131wny"/><path class="pvt39jcep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:orange-book" {...props}></Icon>
