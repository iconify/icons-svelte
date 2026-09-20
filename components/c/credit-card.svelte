<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gikm-gb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gikm-gb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:credit-card" {...props}></Icon>
