<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9d8-lb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9d8-lb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googledataflow" {...props}></Icon>
