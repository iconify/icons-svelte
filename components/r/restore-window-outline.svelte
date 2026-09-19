<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv0npubkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv0npubkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:restore-window-outline" {...props}></Icon>
