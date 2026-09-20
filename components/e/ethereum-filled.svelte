<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1le-zbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t1le-zbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ethereum-filled" {...props}></Icon>
