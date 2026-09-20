<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmnc_7bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmnc_7bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:gitlab" {...props}></Icon>
