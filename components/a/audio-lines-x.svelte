<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6l48392x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6l48392x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:audio-lines-x" {...props}></Icon>
