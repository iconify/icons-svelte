<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srcjumbtm.css';
import '../../css/n/nsza0ub4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srcjumbtm"/><path clip-rule="evenodd" class="nsza0ub4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-add-outline" {...props}></Icon>
