<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk3i2mpof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk3i2mpof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gleam" {...props}></Icon>
