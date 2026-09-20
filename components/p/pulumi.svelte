<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0pp9_tey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0pp9_tey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pulumi" {...props}></Icon>
