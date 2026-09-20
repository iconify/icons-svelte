<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r05oocb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r05oocb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chevron-expand-y-filled" {...props}></Icon>
