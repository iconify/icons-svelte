<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpaos2b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lpaos2b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:rectangle-small" {...props}></Icon>
