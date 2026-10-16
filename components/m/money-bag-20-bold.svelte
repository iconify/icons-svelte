<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdui42b6r.css';
import '../../css/j/j6e6uqpop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jdui42b6r"/><path class="j6e6uqpop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:money-bag-20-bold" {...props}></Icon>
