<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlf9xobuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="hlf9xobuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:password1" {...props}></Icon>
