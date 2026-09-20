<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hltu5yboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hltu5yboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:laptop3-filled" {...props}></Icon>
