<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqxoy3bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cqxoy3bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:hourglass-solid" {...props}></Icon>
