<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv96-jbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv96-jbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ntfy" {...props}></Icon>
