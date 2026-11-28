<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-h8j4bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-h8j4bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pin-off-solid" {...props}></Icon>
