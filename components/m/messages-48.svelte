<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lre1b2w1l.css';
import '../../css/b/b7wt3uvay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lre1b2w1l"/><path class="b7wt3uvay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:messages-48" {...props}></Icon>
