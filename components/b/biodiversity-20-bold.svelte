<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb8flhcid.css';
import '../../css/d/dd0hmgdze.css';
import '../../css/j/jaycibc_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qb8flhcid"/><path class="dd0hmgdze"/><path class="jaycibc_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:biodiversity-20-bold" {...props}></Icon>
