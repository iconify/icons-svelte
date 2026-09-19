<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3pyk_bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e3pyk_bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:apache" {...props}></Icon>
