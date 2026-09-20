<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp5pp2vac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp5pp2vac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrows-up-right" {...props}></Icon>
