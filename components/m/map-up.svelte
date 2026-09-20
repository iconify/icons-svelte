<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbwfzrb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbwfzrb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-up" {...props}></Icon>
