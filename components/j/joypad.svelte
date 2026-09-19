<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfccs038u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qfccs038u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:joypad" {...props}></Icon>
