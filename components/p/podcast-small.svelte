<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sni5zobtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sni5zobtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:podcast-small" {...props}></Icon>
