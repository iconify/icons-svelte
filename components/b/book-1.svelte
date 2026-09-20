<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc7vbnb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vc7vbnb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:book-1" {...props}></Icon>
