<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5wonbc3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l5wonbc3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ghostfolio-dark" {...props}></Icon>
