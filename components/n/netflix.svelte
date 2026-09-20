<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe3j3gbqd.css';
import '../../css/u/uruqrcc2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xe3j3gbqd"/><path class="uruqrcc2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netflix" {...props}></Icon>
