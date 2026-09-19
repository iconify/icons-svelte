<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzkmd1-7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzkmd1-7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bravia" {...props}></Icon>
