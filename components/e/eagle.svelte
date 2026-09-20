<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw4xmd8rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw4xmd8rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:eagle" {...props}></Icon>
