<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur0h5ubxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur0h5ubxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:hierarchy-business-2" {...props}></Icon>
