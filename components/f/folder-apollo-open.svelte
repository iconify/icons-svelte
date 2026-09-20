<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_02szb5c.css';
import '../../css/t/tw_m98bcm.css';
import '../../css/f/fgnd1rb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q_02szb5c"/><path class="tw_m98bcm"/><path class="fgnd1rb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-apollo-open" {...props}></Icon>
