<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_zilyvrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="v_zilyvrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dagger" {...props}></Icon>
