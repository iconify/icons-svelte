<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytc8hsbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytc8hsbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:piwigo" {...props}></Icon>
