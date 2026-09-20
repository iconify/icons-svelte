<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcsw2jb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-1.5};
const content = `<path class="wcsw2jb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:egg-f" {...props}></Icon>
