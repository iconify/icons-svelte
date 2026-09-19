<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk9nfbbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk9nfbbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:more-tv" {...props}></Icon>
