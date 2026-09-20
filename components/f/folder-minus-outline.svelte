<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5ppxm0by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5ppxm0by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-minus-outline" {...props}></Icon>
