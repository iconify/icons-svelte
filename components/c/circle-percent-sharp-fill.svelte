<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9ree0-jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m9ree0-jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-percent-sharp-fill" {...props}></Icon>
