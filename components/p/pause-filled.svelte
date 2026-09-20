<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aygw8acrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aygw8acrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pause-filled" {...props}></Icon>
