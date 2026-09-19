<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbgmjnuri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mbgmjnuri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:phone2x-outline" {...props}></Icon>
