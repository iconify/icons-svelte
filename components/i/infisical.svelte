<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6gs6rbtb.css';
import '../../css/m/mf-rqbcch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j6gs6rbtb"/><path class="mf-rqbcch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:infisical" {...props}></Icon>
