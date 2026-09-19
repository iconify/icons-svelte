<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gljv7l19y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gljv7l19y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:restart" {...props}></Icon>
