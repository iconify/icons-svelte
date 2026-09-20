<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiww6dmoc.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v7inorjqj.css';
import '../../css/o/o11gx5bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="fiww6dmoc"/><g class="cuyn6tgcc"><path class="v7inorjqj"/><path class="o11gx5bhr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:calendar" {...props}></Icon>
