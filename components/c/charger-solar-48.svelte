<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8xpsfbik.css';
import '../../css/y/yn9nkwljy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n8xpsfbik"/><path class="yn9nkwljy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-solar-48" {...props}></Icon>
