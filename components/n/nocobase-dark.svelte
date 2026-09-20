<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5f0jpb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u5f0jpb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nocobase-dark" {...props}></Icon>
