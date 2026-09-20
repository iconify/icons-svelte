<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljc6226xi.css';
import '../../css/u/uqoy3wbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ljc6226xi"/><path class="uqoy3wbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-lending" {...props}></Icon>
