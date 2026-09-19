<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpt2i3bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qpt2i3bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:person-planet-earth" {...props}></Icon>
