<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gue-6fjdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gue-6fjdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:maintenance-triangle-filled" {...props}></Icon>
