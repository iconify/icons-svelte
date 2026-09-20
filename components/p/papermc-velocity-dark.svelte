<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qja8evbtd.css';
import '../../css/q/qitu6dbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qja8evbtd"/><path class="qitu6dbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermc-velocity-dark" {...props}></Icon>
