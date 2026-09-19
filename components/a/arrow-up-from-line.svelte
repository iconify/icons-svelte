<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoa99fbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoa99fbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-up-from-line" {...props}></Icon>
