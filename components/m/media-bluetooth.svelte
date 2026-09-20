<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gog1tmbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gog1tmbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-bluetooth" {...props}></Icon>
