<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezbkiqbhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezbkiqbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:globe-fill" {...props}></Icon>
