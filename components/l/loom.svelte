<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unumhvbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b unumhvbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:loom" {...props}></Icon>
