<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vya2bnlvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vya2bnlvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:radar4-filled" {...props}></Icon>
