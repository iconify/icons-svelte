<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as1jbkb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="as1jbkb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:post-office-10" {...props}></Icon>
