<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p31nrpb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="p31nrpb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:invert" {...props}></Icon>
