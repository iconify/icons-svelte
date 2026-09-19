<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orhr1cbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orhr1cbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:gift-top" {...props}></Icon>
