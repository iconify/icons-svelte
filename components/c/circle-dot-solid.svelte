<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owqwa5b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owqwa5b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:circle-dot-solid" {...props}></Icon>
