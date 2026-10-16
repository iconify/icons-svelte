<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6_n-55ky.css';
import '../../css/r/r4-rvcapq.css';
import '../../css/g/ggak2qltj.css';
import '../../css/y/y9mg2tbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p6_n-55ky"/><path class="r4-rvcapq"/><path class="ggak2qltj"/><path class="y9mg2tbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:package-check-48-bold" {...props}></Icon>
