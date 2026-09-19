<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivck_9bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivck_9bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:garbage-cardboard" {...props}></Icon>
