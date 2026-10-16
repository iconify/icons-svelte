<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovghy0yrs.css';
import '../../css/a/a-nh-q2mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ovghy0yrs"/><path class="a-nh-q2mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hacksaw-48" {...props}></Icon>
