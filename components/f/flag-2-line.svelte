<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ple43knzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ple43knzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flag-2-line" {...props}></Icon>
