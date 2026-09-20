<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoer9n1kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uoer9n1kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:maximize-square2-filled" {...props}></Icon>
