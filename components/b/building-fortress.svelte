<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbnv7fbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbnv7fbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-fortress" {...props}></Icon>
