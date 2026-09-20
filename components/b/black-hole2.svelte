<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0lb7jblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0lb7jblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:black-hole2" {...props}></Icon>
