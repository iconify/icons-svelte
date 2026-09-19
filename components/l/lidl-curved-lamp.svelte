<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajfu422ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajfu422ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lidl-curved-lamp" {...props}></Icon>
