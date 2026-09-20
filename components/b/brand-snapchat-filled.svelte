<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv5yvkbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv5yvkbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-snapchat-filled" {...props}></Icon>
