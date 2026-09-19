<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt73-jbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt73-jbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:list-x" {...props}></Icon>
