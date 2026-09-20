<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqaqp2cek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqaqp2cek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lock-keyhole-open2-filled" {...props}></Icon>
