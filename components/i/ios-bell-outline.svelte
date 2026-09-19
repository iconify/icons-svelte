<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo12tqr8l.css';
import '../../css/n/nidir5bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qo12tqr8l"/><path class="nidir5bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-bell-outline" {...props}></Icon>
