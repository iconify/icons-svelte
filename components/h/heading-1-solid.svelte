<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz931_bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz931_bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:heading-1-solid" {...props}></Icon>
