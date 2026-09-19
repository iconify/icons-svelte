<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbf5-9nsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbf5-9nsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-left-01" {...props}></Icon>
