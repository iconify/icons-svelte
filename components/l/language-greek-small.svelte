<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc2ln7gjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fc2ln7gjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-greek-small" {...props}></Icon>
