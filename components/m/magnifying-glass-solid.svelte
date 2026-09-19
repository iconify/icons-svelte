<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhxadt-mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhxadt-mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:magnifying-glass-solid" {...props}></Icon>
