<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyte5s28l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyte5s28l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:location-light" {...props}></Icon>
