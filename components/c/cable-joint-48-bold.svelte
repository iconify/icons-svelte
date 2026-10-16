<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob4lgh48c.css';
import '../../css/k/k5v_esb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ob4lgh48c"/><path class="k5v_esb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-joint-48-bold" {...props}></Icon>
