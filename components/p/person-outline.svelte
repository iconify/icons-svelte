<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq9psoxhe.css';
import '../../css/u/uzllidbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jq9psoxhe"/><path class="uzllidbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:person-outline" {...props}></Icon>
