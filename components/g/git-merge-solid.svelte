<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-tp1gbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l-tp1gbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:git-merge-solid" {...props}></Icon>
