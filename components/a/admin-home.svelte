<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7v9i8ifs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a7v9i8ifs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-home" {...props}></Icon>
