<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0_z9mbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n0_z9mbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:check-list-square-filled" {...props}></Icon>
