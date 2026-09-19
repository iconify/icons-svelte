<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt-qzxb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":646};
const content = `<path class="mt-qzxb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:cut" {...props}></Icon>
