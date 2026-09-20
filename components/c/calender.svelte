<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzj0jobev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nzj0jobev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:calender" {...props}></Icon>
