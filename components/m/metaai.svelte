<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2_dl55yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2_dl55yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:metaai" {...props}></Icon>
