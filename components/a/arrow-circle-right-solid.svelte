<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egh4-2-bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egh4-2-bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-circle-right-solid" {...props}></Icon>
