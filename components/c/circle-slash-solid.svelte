<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr1e3j9gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr1e3j9gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-slash-solid" {...props}></Icon>
