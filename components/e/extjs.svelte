<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1-wjbbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g1-wjbbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:extjs" {...props}></Icon>
