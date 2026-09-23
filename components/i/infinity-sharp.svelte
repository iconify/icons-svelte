<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4dwjys8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4dwjys8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:infinity-sharp" {...props}></Icon>
