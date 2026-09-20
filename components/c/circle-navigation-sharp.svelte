<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvtt6wbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvtt6wbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-navigation-sharp" {...props}></Icon>
