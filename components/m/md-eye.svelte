<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf467nb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wf467nb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-eye" {...props}></Icon>
