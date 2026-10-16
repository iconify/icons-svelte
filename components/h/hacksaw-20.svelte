<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7xjbxbqp.css';
import '../../css/m/mi71ysxct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i7xjbxbqp"/><path class="mi71ysxct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hacksaw-20" {...props}></Icon>
