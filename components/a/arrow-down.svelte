<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyhatxm3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kyhatxm3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-down" {...props}></Icon>
