<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nye6a6pnu.css';
import '../../css/j/jez9isbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nye6a6pnu"/><path clip-rule="evenodd" class="jez9isbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:camera-16-solid" {...props}></Icon>
