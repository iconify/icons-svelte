<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqwgx2boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqwgx2boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:emoji-talking-angry" {...props}></Icon>
