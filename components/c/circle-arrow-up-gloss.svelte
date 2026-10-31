<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb5lmg94y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sb5lmg94y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-arrow-up-gloss" {...props}></Icon>
