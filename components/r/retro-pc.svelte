<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot1g9j7yp.css';
import '../../css/f/fh44hvb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot1g9j7yp"/><path class="fh44hvb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:retro-pc" {...props}></Icon>
