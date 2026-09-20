<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-dk98buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b-dk98buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensuse-evergreen" {...props}></Icon>
