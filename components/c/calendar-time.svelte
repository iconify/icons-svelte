<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0n602b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i0n602b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:calendar-time" {...props}></Icon>
