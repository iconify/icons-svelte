<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo9gfdykd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo9gfdykd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:askfm" {...props}></Icon>
