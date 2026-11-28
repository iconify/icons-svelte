<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clmd0uhan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clmd0uhan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bag-plus" {...props}></Icon>
