<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqrj2zbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rqrj2zbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-pause-sharp-fill" {...props}></Icon>
