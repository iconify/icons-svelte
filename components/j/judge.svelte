<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_zgeel5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_zgeel5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:judge" {...props}></Icon>
