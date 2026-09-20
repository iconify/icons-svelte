<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdn6t9hua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdn6t9hua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:laptop2-filled" {...props}></Icon>
