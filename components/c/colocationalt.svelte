<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un4folb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="un4folb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:colocationalt" {...props}></Icon>
