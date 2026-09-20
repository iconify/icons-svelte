<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9n2uhbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9n2uhbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:badge-dollar-solid" {...props}></Icon>
