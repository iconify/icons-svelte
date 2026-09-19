<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx9m-lbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bx9m-lbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:bluetooth-fill" {...props}></Icon>
