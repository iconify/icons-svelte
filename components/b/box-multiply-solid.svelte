<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l56gk9tyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="l56gk9tyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:box-multiply-solid" {...props}></Icon>
