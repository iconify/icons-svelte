<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1u-ccs4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1u-ccs4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-compare-fill-round" {...props}></Icon>
