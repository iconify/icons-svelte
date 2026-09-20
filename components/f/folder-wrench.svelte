<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euz9sykji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="euz9sykji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-wrench" {...props}></Icon>
