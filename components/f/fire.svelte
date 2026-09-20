<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6of52qil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6of52qil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:fire" {...props}></Icon>
