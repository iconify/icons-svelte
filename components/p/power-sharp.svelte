<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lloikpa_g.css';
import '../../css/g/glhuhnb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lloikpa_g"/><path class="glhuhnb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:power-sharp" {...props}></Icon>
