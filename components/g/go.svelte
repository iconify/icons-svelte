<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv4xhucbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv4xhucbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:go" {...props}></Icon>
