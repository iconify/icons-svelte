<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj4-u8bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj4-u8bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:minus-small" {...props}></Icon>
