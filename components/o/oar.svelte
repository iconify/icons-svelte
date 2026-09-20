<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v59gcrb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v59gcrb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:oar" {...props}></Icon>
