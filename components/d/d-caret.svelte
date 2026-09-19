<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1uiy8bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n1uiy8bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:d-caret" {...props}></Icon>
