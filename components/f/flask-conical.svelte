<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhrpp3bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhrpp3bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flask-conical" {...props}></Icon>
