<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfg-xccrw.css';
import '../../css/q/qo397l2vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cfg-xccrw"/><path class="qo397l2vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-phone-landscape" {...props}></Icon>
