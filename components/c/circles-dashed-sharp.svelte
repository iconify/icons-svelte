<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-0ed840g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-0ed840g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circles-dashed-sharp" {...props}></Icon>
