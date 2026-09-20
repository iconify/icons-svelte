<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqn5tq0nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="eqn5tq0nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:compass" {...props}></Icon>
