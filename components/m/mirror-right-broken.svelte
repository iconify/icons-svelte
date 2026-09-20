<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d_kca498a.css';
import '../../css/j/jn20mc0cj.css';
import '../../css/c/cipdabcte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d_kca498a"/><path class="jn20mc0cj"/><path class="cipdabcte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mirror-right-broken" {...props}></Icon>
