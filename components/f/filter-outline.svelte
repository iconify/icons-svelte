<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz-n4tbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mz-n4tbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:filter-outline" {...props}></Icon>
