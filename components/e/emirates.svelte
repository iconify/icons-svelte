<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyyqvniyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyyqvniyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:emirates" {...props}></Icon>
