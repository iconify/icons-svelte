<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6wbwjb8t.css';
import '../../css/l/l2frilr8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f6wbwjb8t"/><path class="l2frilr8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:book-marked-48-bold" {...props}></Icon>
