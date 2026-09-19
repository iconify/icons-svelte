<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbzh3mn8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jbzh3mn8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:brightnessfull" {...props}></Icon>
