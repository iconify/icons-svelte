<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivclsta8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivclsta8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid-edit-filled" {...props}></Icon>
