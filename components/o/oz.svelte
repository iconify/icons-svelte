<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm8f8_abp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mm8f8_abp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:oz" {...props}></Icon>
