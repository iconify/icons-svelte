<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwae5qbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwae5qbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nxra" {...props}></Icon>
