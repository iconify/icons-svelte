<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsqabgb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zsqabgb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bookmark-square-solid" {...props}></Icon>
