<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-0k6ir6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-0k6ir6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fuel-fill-round" {...props}></Icon>
