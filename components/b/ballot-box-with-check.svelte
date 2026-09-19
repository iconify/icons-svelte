<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivbhlbb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ivbhlbb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:ballot-box-with-check" {...props}></Icon>
