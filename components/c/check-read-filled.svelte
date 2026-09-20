<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohyzbwbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ohyzbwbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:check-read-filled" {...props}></Icon>
