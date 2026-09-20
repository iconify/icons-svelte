<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4rzdlm4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b4rzdlm4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:french-fries-16" {...props}></Icon>
