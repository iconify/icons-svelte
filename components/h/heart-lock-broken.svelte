<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u0ck9yb3g.css';
import '../../css/u/un29iqbuk.css';
import '../../css/f/fuprorb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u0ck9yb3g"/><path class="un29iqbuk"/><path class="fuprorb1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-lock-broken" {...props}></Icon>
