<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxv3ztb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxv3ztb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:apachefreemarker" {...props}></Icon>
