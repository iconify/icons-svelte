<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4qbnkxxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="s4qbnkxxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:folder-circle" {...props}></Icon>
