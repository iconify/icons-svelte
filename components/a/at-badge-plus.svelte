<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw6wd9x6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="iw6wd9x6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:at-badge-plus" {...props}></Icon>
