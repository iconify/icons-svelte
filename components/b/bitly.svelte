<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa5efpwgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa5efpwgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bitly" {...props}></Icon>
