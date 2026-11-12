<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7yjv0aal.css';
import '../../css/x/xca1i3bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y7yjv0aal"/><path class="xca1i3bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crow-ci-dark" {...props}></Icon>
