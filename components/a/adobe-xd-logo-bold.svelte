<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbw9uccby.css';
import '../../css/k/k0dwhb53f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbw9uccby"/><path class="k0dwhb53f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:adobe-xd-logo-bold" {...props}></Icon>
