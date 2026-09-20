<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc50gibdd.css';
import '../../css/v/v691k0tbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="rc50gibdd"/><path clip-rule="evenodd" class="v691k0tbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pinepods-dark" {...props}></Icon>
