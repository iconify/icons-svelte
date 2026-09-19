<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wenidnb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wenidnb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:insert-template" {...props}></Icon>
