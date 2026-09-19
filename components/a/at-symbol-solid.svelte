<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2vky6jpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y2vky6jpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:at-symbol-solid" {...props}></Icon>
