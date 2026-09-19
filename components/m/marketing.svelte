<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/z05uk-bek.css';
import '../../css/t/t4zxnwuot.css';
import '../../css/q/qpz7cvbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><ellipse class="z05uk-bek"/><path class="t4zxnwuot"/><path class="qpz7cvbsd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:marketing" {...props}></Icon>
