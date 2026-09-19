<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb21tnwxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fb21tnwxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:group-23-solid" {...props}></Icon>
