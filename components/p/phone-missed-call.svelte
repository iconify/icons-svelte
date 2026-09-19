<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj0yd0xaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj0yd0xaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:phone-missed-call" {...props}></Icon>
