<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi2996b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gi2996b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:binocular-solid" {...props}></Icon>
