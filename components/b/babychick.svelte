<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsoix_jkw.css';
import '../../css/f/f_yv0yb3g.css';
import '../../css/p/pr0kgdb0u.css';
import '../../css/c/cvziz8baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rsoix_jkw"/><path class="f_yv0yb3g"/><path class="pr0kgdb0u"/><path class="cvziz8baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:babychick" {...props}></Icon>
