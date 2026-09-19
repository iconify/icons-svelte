<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj9qltbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj9qltbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mercedes" {...props}></Icon>
