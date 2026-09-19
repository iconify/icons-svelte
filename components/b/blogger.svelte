<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mff0z4bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":990.933,"height":1000};
const content = `<path class="mff0z4bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:blogger" {...props}></Icon>
