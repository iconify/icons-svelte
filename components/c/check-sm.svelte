<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nml4g8bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="nml4g8bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:check-sm" {...props}></Icon>
