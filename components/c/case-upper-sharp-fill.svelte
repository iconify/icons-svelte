<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg-_syi2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg-_syi2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:case-upper-sharp-fill" {...props}></Icon>
