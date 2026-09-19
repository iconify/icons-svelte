<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcasx0bxr.css';
import '../../css/n/n980ub85d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcasx0bxr"/><path class="n980ub85d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:monitoring" {...props}></Icon>
