<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3m-0_wes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h3m-0_wes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gitlab-16" {...props}></Icon>
