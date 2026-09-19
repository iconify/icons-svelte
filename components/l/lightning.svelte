<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcn8ucyih.css';
import '../../css/j/j62e8oyno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bcn8ucyih"/><path class="j62e8oyno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:lightning" {...props}></Icon>
