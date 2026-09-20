<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynsie1h8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynsie1h8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:c" {...props}></Icon>
