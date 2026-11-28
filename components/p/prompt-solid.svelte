<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z21k9mb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z21k9mb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:prompt-solid" {...props}></Icon>
