<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grb9lfb6x.css';
import '../../css/n/n3dlx8buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="grb9lfb6x"/><path class="n3dlx8buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quire-ink-light" {...props}></Icon>
