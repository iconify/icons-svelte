<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjigr4ppa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjigr4ppa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gallery-horizontal-end" {...props}></Icon>
