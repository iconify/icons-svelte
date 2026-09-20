<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2v1743-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2v1743-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lock-keyhole-open-filled" {...props}></Icon>
