<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyrrl6b4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyrrl6b4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-success-fill" {...props}></Icon>
