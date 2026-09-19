<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4qrpmb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4qrpmb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:arrow-down" {...props}></Icon>
