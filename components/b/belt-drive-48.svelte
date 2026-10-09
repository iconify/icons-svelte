<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pouv5lbnl.css';
import '../../css/q/qqjnhll6v.css';
import '../../css/e/efnr8lb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pouv5lbnl"/><path class="qqjnhll6v"/><path class="efnr8lb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:belt-drive-48" {...props}></Icon>
