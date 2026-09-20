<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbsxuj1jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="vbsxuj1jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:border-all-solid" {...props}></Icon>
