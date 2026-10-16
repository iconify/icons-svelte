<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6t120hgc.css';
import '../../css/b/b-cut7-tv.css';
import '../../css/i/iqqj1-bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z6t120hgc"/><path class="b-cut7-tv"/><path class="iqqj1-bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-copy-20-bold" {...props}></Icon>
