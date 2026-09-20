<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq8sby3jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq8sby3jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gps-slash-filled" {...props}></Icon>
