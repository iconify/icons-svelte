<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxd7rab2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="oxd7rab2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:church" {...props}></Icon>
