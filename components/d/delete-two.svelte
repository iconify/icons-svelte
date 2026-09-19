<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt1r6l-8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lt1r6l-8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:delete-two" {...props}></Icon>
