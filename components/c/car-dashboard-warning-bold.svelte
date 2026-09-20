<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt3335b0v.css';
import '../../css/x/x35aq7bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt3335b0v"/><path class="x35aq7bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:car-dashboard-warning-bold" {...props}></Icon>
