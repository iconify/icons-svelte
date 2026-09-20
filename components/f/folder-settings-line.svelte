<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi6y_vvsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi6y_vvsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-settings-line" {...props}></Icon>
