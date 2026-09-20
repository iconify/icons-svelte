<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn56070pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn56070pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:controller-xbox" {...props}></Icon>
