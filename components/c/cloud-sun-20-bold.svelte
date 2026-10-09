<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xro2jqn5o.css';
import '../../css/q/qe8sicbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xro2jqn5o"/><path class="qe8sicbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-sun-20-bold" {...props}></Icon>
