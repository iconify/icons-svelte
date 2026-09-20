<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q19gspbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q19gspbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-x-sharp-fill" {...props}></Icon>
