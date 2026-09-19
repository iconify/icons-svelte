<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmrs85b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pmrs85b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:check-small" {...props}></Icon>
