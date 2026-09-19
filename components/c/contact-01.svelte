<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/y0djph_hu.css';
import '../../css/b/b51061zzw.css';
import '../../css/j/j9d1q1wok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><rect class="y0djph_hu"/><path class="b51061zzw"/><path class="j9d1q1wok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:contact-01" {...props}></Icon>
