<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um4tz2b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um4tz2b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-code-sharp-fill" {...props}></Icon>
