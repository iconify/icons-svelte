<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghya2o-_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ghya2o-_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:orange" {...props}></Icon>
