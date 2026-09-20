<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn57_fb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn57_fb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:primevideo" {...props}></Icon>
