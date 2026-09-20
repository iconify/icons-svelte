<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft1i4rbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft1i4rbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:layers-clear" {...props}></Icon>
