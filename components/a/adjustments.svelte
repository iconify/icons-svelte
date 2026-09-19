<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs1_jt4ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vs1_jt4ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adjustments" {...props}></Icon>
