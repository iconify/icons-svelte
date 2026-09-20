<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_32m8bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l_32m8bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:eslint-16" {...props}></Icon>
