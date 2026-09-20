<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwfrq7b_a.css';
import '../../css/v/v27rigbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwfrq7b_a"/><path clip-rule="evenodd" class="v27rigbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:omni" {...props}></Icon>
