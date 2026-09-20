<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhut4zpns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhut4zpns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:presentation-filled" {...props}></Icon>
