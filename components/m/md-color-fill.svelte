<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9w0_3bdd.css';
import '../../css/g/gyiiqfa7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h9w0_3bdd"/><path class="gyiiqfa7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-color-fill" {...props}></Icon>
