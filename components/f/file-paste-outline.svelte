<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egt-gsfjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egt-gsfjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-paste-outline" {...props}></Icon>
