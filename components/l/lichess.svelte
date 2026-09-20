<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_4mbzbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_4mbzbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lichess" {...props}></Icon>
