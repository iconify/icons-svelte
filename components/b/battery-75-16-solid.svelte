<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iybqfvbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iybqfvbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:battery-75-16-solid" {...props}></Icon>
