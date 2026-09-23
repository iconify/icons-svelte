<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w56k6_btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w56k6_btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:corner-left-down-sharp-fill" {...props}></Icon>
