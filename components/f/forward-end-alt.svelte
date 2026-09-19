<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o59bf8-pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="o59bf8-pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:forward-end-alt" {...props}></Icon>
