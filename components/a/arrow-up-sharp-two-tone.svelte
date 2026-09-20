<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_ffkvbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_ffkvbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-sharp-two-tone" {...props}></Icon>
