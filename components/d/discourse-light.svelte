<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm8kr_b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vm8kr_b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:discourse-light" {...props}></Icon>
