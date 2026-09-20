<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm9y4iblw.css';
import '../../css/z/zkrbon-zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm9y4iblw"/><path class="zkrbon-zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:palace-4-filled" {...props}></Icon>
