<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpgdgjb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":448};
const content = `<path class="fpgdgjb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:asterisk" {...props}></Icon>
