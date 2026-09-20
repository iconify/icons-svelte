<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4mcjdb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-1.5};
const content = `<path class="d4mcjdb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:branch-f" {...props}></Icon>
