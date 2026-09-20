<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb0ly6wwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb0ly6wwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cal-com" {...props}></Icon>
