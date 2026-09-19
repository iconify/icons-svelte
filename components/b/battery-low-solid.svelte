<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqcs72gla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yqcs72gla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:battery-low-solid" {...props}></Icon>
