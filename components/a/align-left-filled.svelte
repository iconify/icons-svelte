<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sohb-3b4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sohb-3b4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:align-left-filled" {...props}></Icon>
