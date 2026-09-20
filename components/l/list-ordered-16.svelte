<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-kpfab6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v-kpfab6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:list-ordered-16" {...props}></Icon>
