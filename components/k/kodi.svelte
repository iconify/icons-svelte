<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxomwl-ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxomwl-ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kodi" {...props}></Icon>
