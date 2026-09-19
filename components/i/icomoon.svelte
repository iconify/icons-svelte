<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kazgz6b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kazgz6b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:icomoon" {...props}></Icon>
