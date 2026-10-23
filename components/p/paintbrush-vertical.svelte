<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcb8d9bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcb8d9bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:paintbrush-vertical" {...props}></Icon>
