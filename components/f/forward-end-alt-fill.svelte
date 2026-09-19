<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc9wkibkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="oc9wkibkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:forward-end-alt-fill" {...props}></Icon>
