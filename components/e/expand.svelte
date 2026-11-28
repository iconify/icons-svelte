<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj1g30blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj1g30blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:expand" {...props}></Icon>
