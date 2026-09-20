<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhgsonb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhgsonb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:archway-1-filled" {...props}></Icon>
