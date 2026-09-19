<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw56jtzlm.css';
import '../../css/i/i7gp9cbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw56jtzlm"/><path class="i7gp9cbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chevrons-up" {...props}></Icon>
