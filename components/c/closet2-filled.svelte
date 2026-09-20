<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6t49zkgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w6t49zkgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:closet2-filled" {...props}></Icon>
