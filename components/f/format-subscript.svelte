<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf5ezfqel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf5ezfqel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-subscript" {...props}></Icon>
