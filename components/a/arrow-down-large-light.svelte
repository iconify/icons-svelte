<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voeg6obyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voeg6obyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-down-large-light" {...props}></Icon>
