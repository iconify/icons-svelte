<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4v7gpb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="o4v7gpb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:brailled" {...props}></Icon>
