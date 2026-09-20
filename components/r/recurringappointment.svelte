<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv55mnb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="nv55mnb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:recurringappointment" {...props}></Icon>
