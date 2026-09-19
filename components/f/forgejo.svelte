<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9ma__bqh.css';
import '../../css/t/td4gnzb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f9ma__bqh"/><path class="td4gnzb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:forgejo" {...props}></Icon>
