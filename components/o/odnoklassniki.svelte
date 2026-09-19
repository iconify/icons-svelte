<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd-no5pjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wd-no5pjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:odnoklassniki" {...props}></Icon>
