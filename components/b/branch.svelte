<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1243xbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1243xbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:branch" {...props}></Icon>
