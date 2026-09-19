<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p79y4pbes.css';
import '../../css/l/l7avsacre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p79y4pbes"/><circle class="l7avsacre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:notification-new" {...props}></Icon>
