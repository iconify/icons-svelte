<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9jk5xc7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9jk5xc7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:globe" {...props}></Icon>
