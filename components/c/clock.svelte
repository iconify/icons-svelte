<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvqusacuk.css';
import '../../css/p/pe8xatc2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvqusacuk"/><path class="pe8xatc2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:clock" {...props}></Icon>
