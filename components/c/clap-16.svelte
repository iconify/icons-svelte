<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usl3xqbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="usl3xqbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:clap-16" {...props}></Icon>
