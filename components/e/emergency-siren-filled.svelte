<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr1sztbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dr1sztbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:emergency-siren-filled" {...props}></Icon>
