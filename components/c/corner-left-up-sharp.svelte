<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwlud-5vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwlud-5vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:corner-left-up-sharp" {...props}></Icon>
