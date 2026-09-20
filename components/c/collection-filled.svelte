<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s87l4gbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s87l4gbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:collection-filled" {...props}></Icon>
