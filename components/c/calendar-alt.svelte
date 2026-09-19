<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh0-akcec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="eh0-akcec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:calendar-alt" {...props}></Icon>
