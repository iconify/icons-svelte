<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu4wc-bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pu4wc-bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pipenv" {...props}></Icon>
