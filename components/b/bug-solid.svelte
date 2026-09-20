<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpidxr41x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kpidxr41x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bug-solid" {...props}></Icon>
