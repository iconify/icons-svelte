<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd-49accd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd-49accd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notification-bell-upload-fill" {...props}></Icon>
