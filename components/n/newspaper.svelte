<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbq-4rbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbq-4rbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:newspaper" {...props}></Icon>
