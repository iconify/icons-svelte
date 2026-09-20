<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_uzvwaql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="y_uzvwaql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-up-left-fill" {...props}></Icon>
