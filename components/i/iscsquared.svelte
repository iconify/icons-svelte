<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy5e71v4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy5e71v4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:iscsquared" {...props}></Icon>
