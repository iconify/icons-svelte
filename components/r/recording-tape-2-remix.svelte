<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2bpek80n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y2bpek80n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:recording-tape-2-remix" {...props}></Icon>
