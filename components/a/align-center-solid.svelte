<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ure9msbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ure9msbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:align-center-solid" {...props}></Icon>
