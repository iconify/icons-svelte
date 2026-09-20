<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmrph42ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmrph42ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:briefcase-filled" {...props}></Icon>
