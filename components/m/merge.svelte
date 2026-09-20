<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkelu8__e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="bkelu8__e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:merge" {...props}></Icon>
