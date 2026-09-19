<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyj8oqbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyj8oqbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:qatar-airways" {...props}></Icon>
