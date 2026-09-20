<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaw6epbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oaw6epbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:easy-redmine-dark" {...props}></Icon>
