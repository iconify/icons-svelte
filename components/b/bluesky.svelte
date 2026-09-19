<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy1f2qbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy1f2qbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bluesky" {...props}></Icon>
