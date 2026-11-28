<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_19j5tbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_19j5tbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:kite" {...props}></Icon>
