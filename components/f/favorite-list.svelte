<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0g8gybue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m0g8gybue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:favorite-list" {...props}></Icon>
