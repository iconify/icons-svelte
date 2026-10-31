<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8bof-icw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8bof-icw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-u-turn-left-down-round" {...props}></Icon>
