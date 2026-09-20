<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtn8hf62f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtn8hf62f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chart-trend-down-light" {...props}></Icon>
