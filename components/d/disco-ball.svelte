<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwcejpn7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwcejpn7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:disco-ball" {...props}></Icon>
