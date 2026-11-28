<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uklv7lbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uklv7lbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-rain" {...props}></Icon>
