<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6i-kbbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p6i-kbbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nemerle" {...props}></Icon>
