<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_7jr7bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_7jr7bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alarm-arm-night" {...props}></Icon>
