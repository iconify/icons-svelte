<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u83vykqso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="u83vykqso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:isni-square" {...props}></Icon>
