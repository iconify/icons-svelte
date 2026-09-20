<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdew_8bek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bdew_8bek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hang-up-2-solid" {...props}></Icon>
