<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebykjww_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebykjww_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hard-drive-filled" {...props}></Icon>
