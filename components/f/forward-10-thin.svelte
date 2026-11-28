<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjofz7oow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vjofz7oow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:forward-10-thin" {...props}></Icon>
