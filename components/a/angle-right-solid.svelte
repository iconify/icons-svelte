<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvhvk6bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvhvk6bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:angle-right-solid" {...props}></Icon>
