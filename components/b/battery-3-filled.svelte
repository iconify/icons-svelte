<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcw8iw7rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcw8iw7rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-3-filled" {...props}></Icon>
