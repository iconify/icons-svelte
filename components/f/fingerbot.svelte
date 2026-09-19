<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lesudhbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lesudhbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:fingerbot" {...props}></Icon>
