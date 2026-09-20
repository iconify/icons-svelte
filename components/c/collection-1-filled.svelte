<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxd08ei8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxd08ei8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:collection-1-filled" {...props}></Icon>
