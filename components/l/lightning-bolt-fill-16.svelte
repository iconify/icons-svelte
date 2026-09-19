<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_5w63pry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b_5w63pry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lightning-bolt-fill-16" {...props}></Icon>
