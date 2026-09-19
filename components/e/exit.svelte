<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok1drzb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ok1drzb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:exit" {...props}></Icon>
