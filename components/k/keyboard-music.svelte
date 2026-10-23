<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqadbdcao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqadbdcao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:keyboard-music" {...props}></Icon>
