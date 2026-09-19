<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sast5uygs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sast5uygs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-missing" {...props}></Icon>
