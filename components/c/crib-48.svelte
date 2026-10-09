<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k800nzeoy.css';
import '../../css/e/eawggbbqu.css';
import '../../css/z/z7c6bib6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k800nzeoy"/><path class="eawggbbqu"/><path class="z7c6bib6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crib-48" {...props}></Icon>
