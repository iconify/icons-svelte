<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3a2ybb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q3a2ybb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:passport-globe-solid" {...props}></Icon>
