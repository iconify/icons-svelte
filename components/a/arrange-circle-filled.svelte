<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdwd_9gor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdwd_9gor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrange-circle-filled" {...props}></Icon>
