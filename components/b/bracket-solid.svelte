<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnkgj4m4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xnkgj4m4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bracket-solid" {...props}></Icon>
