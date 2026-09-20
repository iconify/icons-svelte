<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpvzf-btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpvzf-btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heat-cool" {...props}></Icon>
