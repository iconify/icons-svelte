<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzgp6absl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzgp6absl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:html5" {...props}></Icon>
