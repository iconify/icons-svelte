<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chhvm5r4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="chhvm5r4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gallery2-filled" {...props}></Icon>
