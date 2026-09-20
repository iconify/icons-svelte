<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3g-2fu1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3g-2fu1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:abbott" {...props}></Icon>
