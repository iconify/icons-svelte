<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw-6j-kcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw-6j-kcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:command3-filled" {...props}></Icon>
