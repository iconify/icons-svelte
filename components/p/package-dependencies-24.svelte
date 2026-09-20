<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1_z_4b0d.css';
import '../../css/e/esp72qa9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1_z_4b0d"/><path class="esp72qa9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:package-dependencies-24" {...props}></Icon>
