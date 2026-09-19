<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiv10dbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eiv10dbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-ceiling-square" {...props}></Icon>
