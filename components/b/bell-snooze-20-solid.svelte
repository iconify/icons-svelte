<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6cvcobix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="v6cvcobix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell-snooze-20-solid" {...props}></Icon>
