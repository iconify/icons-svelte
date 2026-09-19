<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbjz_f1qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sbjz_f1qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:gitlab" {...props}></Icon>
