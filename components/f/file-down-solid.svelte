<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgvtg0iqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgvtg0iqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-down-solid" {...props}></Icon>
