<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i10-u0blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="i10-u0blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:calendar-alt" {...props}></Icon>
