<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s59vm9a0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s59vm9a0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:headset-outline" {...props}></Icon>
