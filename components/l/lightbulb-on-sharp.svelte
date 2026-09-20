<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3g2qub8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3g2qub8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:lightbulb-on-sharp" {...props}></Icon>
