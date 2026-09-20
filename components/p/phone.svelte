<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs55nrb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs55nrb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:phone" {...props}></Icon>
