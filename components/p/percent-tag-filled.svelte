<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niv9iacmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="niv9iacmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:percent-tag-filled" {...props}></Icon>
