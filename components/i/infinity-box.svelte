<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geijyubyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geijyubyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:infinity-box" {...props}></Icon>
