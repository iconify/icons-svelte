<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boh2k7bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="boh2k7bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bitwarden" {...props}></Icon>
