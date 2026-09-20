<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8-97cbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y8-97cbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:calendar-add-solid" {...props}></Icon>
