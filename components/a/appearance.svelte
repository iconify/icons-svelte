<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4s0jmqnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g4s0jmqnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:appearance" {...props}></Icon>
