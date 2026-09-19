<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puoohk0xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="puoohk0xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:insert-rows-below" {...props}></Icon>
