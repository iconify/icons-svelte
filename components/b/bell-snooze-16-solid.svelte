<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixj9blbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ixj9blbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell-snooze-16-solid" {...props}></Icon>
