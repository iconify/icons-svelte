<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeiv6oacw.css';
import '../../css/c/c2jt5db4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oeiv6oacw"/><path class="c2jt5db4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudron" {...props}></Icon>
