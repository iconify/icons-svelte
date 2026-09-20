<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v31u02jyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v31u02jyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flask-remove-outline" {...props}></Icon>
