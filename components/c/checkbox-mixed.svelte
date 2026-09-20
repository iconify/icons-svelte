<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stgx23nhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="stgx23nhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:checkbox-mixed" {...props}></Icon>
