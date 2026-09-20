<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfefyfbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfefyfbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-right-open-sharp" {...props}></Icon>
