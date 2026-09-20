<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/depymg3-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="depymg3-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:closet" {...props}></Icon>
