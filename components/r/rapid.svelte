<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aer--wb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aer--wb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rapid" {...props}></Icon>
