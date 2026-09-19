<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goo-ghg2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="goo-ghg2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:octoloaderfull" {...props}></Icon>
