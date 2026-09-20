<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh6e5bcgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh6e5bcgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:equal" {...props}></Icon>
