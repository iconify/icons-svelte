<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as9abwbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as9abwbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eiffel-tower-fill" {...props}></Icon>
