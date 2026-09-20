<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj3iep4cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj3iep4cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:powerautomate" {...props}></Icon>
