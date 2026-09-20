<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb121mbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb121mbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:module-filled" {...props}></Icon>
