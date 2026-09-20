<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbc1sobbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bbc1sobbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:clear-16" {...props}></Icon>
