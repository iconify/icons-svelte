<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oistvxbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oistvxbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-lightguide-oval" {...props}></Icon>
