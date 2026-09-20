<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq6_t6blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yq6_t6blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lamp-slash-filled" {...props}></Icon>
