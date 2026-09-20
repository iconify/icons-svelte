<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpcox3bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":141.83};
const content = `<path class="qpcox3bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chase-light" {...props}></Icon>
