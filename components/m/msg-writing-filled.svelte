<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aamnv1bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aamnv1bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:msg-writing-filled" {...props}></Icon>
