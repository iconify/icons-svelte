<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl3ctjb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sl3ctjb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bed-linen-filled" {...props}></Icon>
