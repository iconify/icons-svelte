<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teo9tmjwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":627};
const content = `<path class="teo9tmjwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:quote" {...props}></Icon>
