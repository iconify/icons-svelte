<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb7aw7omu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb7aw7omu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:menu-left-outline" {...props}></Icon>
