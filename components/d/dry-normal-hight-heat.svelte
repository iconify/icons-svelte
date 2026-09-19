<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb-3hdh2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kb-3hdh2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:dry-normal-hight-heat" {...props}></Icon>
