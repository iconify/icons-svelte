<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avexz9b5g.css';
import '../../css/i/i5j29cx8h.css';
import '../../css/h/hjv36fv1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="avexz9b5g"/><path class="i5j29cx8h"/><path class="hjv36fv1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-ccs-48-bold" {...props}></Icon>
