<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4nnu3b-h.css';
import '../../css/s/s_rjlabju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i4nnu3b-h"/><path class="s_rjlabju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:linkexternal" {...props}></Icon>
