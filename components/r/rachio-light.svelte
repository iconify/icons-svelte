<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoy-4cccy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qoy-4cccy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rachio-light" {...props}></Icon>
