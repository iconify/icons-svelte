<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffet1q63i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffet1q63i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-merge-conflict-line" {...props}></Icon>
