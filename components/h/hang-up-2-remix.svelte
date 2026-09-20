<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5ae8mb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o5ae8mb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hang-up-2-remix" {...props}></Icon>
