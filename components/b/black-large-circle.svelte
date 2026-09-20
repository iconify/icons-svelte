<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1kn8_3bk.css';
import '../../css/k/kbay0kr8o.css';
import '../../css/t/tlh0720xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="f1kn8_3bk"/><path class="kbay0kr8o"/><path class="tlh0720xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:black-large-circle" {...props}></Icon>
