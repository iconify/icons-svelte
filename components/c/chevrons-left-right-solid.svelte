<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eriz5_bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eriz5_bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevrons-left-right-solid" {...props}></Icon>
