<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrg2b27ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrg2b27ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-pull-request-filled" {...props}></Icon>
