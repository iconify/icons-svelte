<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0g4q_f2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0g4q_f2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:pause-circle" {...props}></Icon>
