<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsewf9bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsewf9bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-arrow-up2-filled" {...props}></Icon>
