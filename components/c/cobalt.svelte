<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybz7xp5wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybz7xp5wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cobalt" {...props}></Icon>
