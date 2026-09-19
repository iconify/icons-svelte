<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugb-_6bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugb-_6bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:delivery-light" {...props}></Icon>
