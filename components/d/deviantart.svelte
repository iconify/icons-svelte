<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg7z6eq8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bg7z6eq8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:deviantart" {...props}></Icon>
