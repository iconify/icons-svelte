<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8v-evrrq.css';
import '../../css/d/d9ypmmcan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o8v-evrrq"/><path class="d9ypmmcan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:hand-awesome" {...props}></Icon>
