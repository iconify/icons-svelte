<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbp06qb8h.css';
import '../../css/h/hpzn55bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rbp06qb8h"/><path class="hpzn55bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:luna-dashboard-dark" {...props}></Icon>
