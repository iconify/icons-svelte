<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9s7yxbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9s7yxbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:christ-the-redeemer-line" {...props}></Icon>
