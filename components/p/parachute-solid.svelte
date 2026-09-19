<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk_v_3bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dk_v_3bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:parachute-solid" {...props}></Icon>
