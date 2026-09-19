<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvf4-gbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="jvf4-gbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:home-fill-26" {...props}></Icon>
