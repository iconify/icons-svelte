<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbykp4bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbykp4bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right5-filled" {...props}></Icon>
