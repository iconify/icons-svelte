<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrqn5eb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nrqn5eb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:arrow-up" {...props}></Icon>
