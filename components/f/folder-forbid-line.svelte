<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uozfgabmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uozfgabmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-forbid-line" {...props}></Icon>
