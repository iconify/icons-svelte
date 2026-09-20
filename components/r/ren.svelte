<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zimitg3op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zimitg3op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ren" {...props}></Icon>
