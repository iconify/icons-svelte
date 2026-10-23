<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgva3g5if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgva3g5if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:philippine-peso" {...props}></Icon>
