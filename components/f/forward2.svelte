<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfstxhi3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kfstxhi3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:forward2" {...props}></Icon>
