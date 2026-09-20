<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc4yfhbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oc4yfhbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hop" {...props}></Icon>
