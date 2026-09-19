<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4km3zbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y4km3zbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:delivery-fast-fill" {...props}></Icon>
