<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfi146w-l.css';
import '../../css/e/eeps4wpgj.css';
import '../../css/y/y9mg2tbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pfi146w-l"/><path class="eeps4wpgj"/><path class="y9mg2tbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-station-check-48-bold" {...props}></Icon>
