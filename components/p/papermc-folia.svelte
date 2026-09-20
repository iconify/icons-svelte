<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdvocgpel.css';
import '../../css/f/f8tiq9b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kdvocgpel"/><path class="f8tiq9b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermc-folia" {...props}></Icon>
