<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbloczr4z.css';
import '../../css/p/p16id-nll.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/ndfjvjb0x.css';
import '../../css/f/fh2q1qbmo.css';
import '../../css/c/cpjgc658y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="hbloczr4z"/><path class="p16id-nll"/><g class="cuyn6tgcc"><path class="ndfjvjb0x"/><path class="fh2q1qbmo"/></g><path class="cpjgc658y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:pinch" {...props}></Icon>
