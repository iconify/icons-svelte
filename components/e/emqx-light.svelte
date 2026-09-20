<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwad7hboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uwad7hboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:emqx-light" {...props}></Icon>
