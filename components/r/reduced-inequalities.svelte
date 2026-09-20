<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwhv-n8ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pwhv-n8ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:reduced-inequalities" {...props}></Icon>
