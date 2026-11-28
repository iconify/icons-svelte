<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc7023fup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc7023fup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-output-solid" {...props}></Icon>
