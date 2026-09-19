<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx54t9boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nx54t9boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:receipt-refund-solid" {...props}></Icon>
