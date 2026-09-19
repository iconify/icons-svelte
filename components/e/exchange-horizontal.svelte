<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdh3jeblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdh3jeblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:exchange-horizontal" {...props}></Icon>
