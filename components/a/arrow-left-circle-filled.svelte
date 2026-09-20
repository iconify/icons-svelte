<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojig1mf8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojig1mf8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-left-circle-filled" {...props}></Icon>
