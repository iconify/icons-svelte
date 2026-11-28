<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyj43hb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyj43hb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heart-crack-solid" {...props}></Icon>
