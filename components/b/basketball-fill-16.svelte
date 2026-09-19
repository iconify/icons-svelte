<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk71zzbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vk71zzbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:basketball-fill-16" {...props}></Icon>
