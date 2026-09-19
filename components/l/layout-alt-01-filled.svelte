<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot4vp4spt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ot4vp4spt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:layout-alt-01-filled" {...props}></Icon>
