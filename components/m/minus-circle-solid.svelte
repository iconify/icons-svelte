<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb6y63g1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xb6y63g1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:minus-circle-solid" {...props}></Icon>
