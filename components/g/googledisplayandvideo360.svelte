<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqc085xkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqc085xkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googledisplayandvideo360" {...props}></Icon>
