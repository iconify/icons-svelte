<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3n0d8bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v3n0d8bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cpr-outline" {...props}></Icon>
