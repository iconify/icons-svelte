<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd-z39bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vd-z39bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:group12-filled" {...props}></Icon>
