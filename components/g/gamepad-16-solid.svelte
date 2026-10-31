<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kebqv84he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kebqv84he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gamepad-16-solid" {...props}></Icon>
