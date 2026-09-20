<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmri_4b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pmri_4b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:norish-light" {...props}></Icon>
