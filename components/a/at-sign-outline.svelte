<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3ccljb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a3ccljb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:at-sign-outline" {...props}></Icon>
