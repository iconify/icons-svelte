<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbo_8fb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbo_8fb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:instapaper-logo" {...props}></Icon>
