<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4v6-8p-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="s4v6-8p-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:news" {...props}></Icon>
