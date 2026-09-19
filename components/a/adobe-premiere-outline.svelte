<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0vn8x9rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b0vn8x9rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:adobe-premiere-outline" {...props}></Icon>
