<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6_6esb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f6_6esb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:loadingalt" {...props}></Icon>
