<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srbg1iv5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="srbg1iv5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:add-notes" {...props}></Icon>
