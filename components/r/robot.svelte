<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvle84btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvle84btf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:robot" {...props}></Icon>
