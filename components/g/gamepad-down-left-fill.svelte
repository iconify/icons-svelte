<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxztuo_we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="kxztuo_we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-down-left-fill" {...props}></Icon>
