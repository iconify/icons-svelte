<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ce5bejr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f6ce5bejr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:database-server-3" {...props}></Icon>
