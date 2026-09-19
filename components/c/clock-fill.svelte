<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv4j13o_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rv4j13o_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:clock-fill" {...props}></Icon>
