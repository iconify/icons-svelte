<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qika6xbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qika6xbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bomb-outline" {...props}></Icon>
