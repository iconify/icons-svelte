<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqbp4ccby.css';
import '../../css/f/fos7arooz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dqbp4ccby"/><path class="fos7arooz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:anchor-bottom-right-16" {...props}></Icon>
