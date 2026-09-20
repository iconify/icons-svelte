<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7qq9eqjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7qq9eqjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:content-save-minus" {...props}></Icon>
