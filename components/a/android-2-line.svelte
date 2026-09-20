<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yszkt334k.css';
import '../../css/t/tj0901bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yszkt334k"/><path class="tj0901bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:android-2-line" {...props}></Icon>
