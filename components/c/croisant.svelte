<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls0it7-zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ls0it7-zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:croisant" {...props}></Icon>
