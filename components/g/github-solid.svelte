<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki94p-fap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki94p-fap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:github-solid" {...props}></Icon>
