<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd-r6lbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd-r6lbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:plus-light" {...props}></Icon>
