<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdtai9brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="bdtai9brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:luggage-trolley" {...props}></Icon>
