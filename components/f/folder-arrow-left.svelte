<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrvmt6s1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrvmt6s1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-arrow-left" {...props}></Icon>
