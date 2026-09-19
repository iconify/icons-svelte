<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otc4z1bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otc4z1bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pendant-round" {...props}></Icon>
