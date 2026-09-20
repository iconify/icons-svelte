<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx-i-d7hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx-i-d7hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:processing-foundation" {...props}></Icon>
