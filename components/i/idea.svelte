<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esul8pbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esul8pbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:idea" {...props}></Icon>
