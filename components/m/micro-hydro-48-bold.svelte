<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb0k45bkf.css';
import '../../css/f/ftn7apb3z.css';
import '../../css/q/qtoznccub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bb0k45bkf"/><path class="ftn7apb3z"/><path class="qtoznccub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:micro-hydro-48-bold" {...props}></Icon>
