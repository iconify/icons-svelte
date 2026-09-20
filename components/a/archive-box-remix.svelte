<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt1k-qwgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nt1k-qwgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:archive-box-remix" {...props}></Icon>
