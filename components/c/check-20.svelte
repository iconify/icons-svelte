<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdxrnm0ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mdxrnm0ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-20" {...props}></Icon>
