<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkbshkqya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkbshkqya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:battery-charging" {...props}></Icon>
