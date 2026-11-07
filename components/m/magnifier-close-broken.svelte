<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c5cjgzbpf.css';
import '../../css/x/x09loybdy.css';
import '../../css/m/my64q2aeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c5cjgzbpf"/><path class="x09loybdy"/><path class="my64q2aeo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-close-broken" {...props}></Icon>
