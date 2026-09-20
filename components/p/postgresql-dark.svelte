<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7lad7bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w7lad7bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:postgresql-dark" {...props}></Icon>
