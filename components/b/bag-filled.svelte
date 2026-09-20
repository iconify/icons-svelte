<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmixd20za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zmixd20za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag-filled" {...props}></Icon>
