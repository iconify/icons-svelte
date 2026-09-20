<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7hi0ksbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="l7hi0ksbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:align-text-left" {...props}></Icon>
