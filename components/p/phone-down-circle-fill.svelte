<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz55hfrey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pz55hfrey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:phone-down-circle-fill" {...props}></Icon>
