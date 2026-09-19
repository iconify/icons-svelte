<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg3fqv7jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fg3fqv7jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:list-number-fill-16" {...props}></Icon>
