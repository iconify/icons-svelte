<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv72_cb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jv72_cb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:paint-bucket-remix" {...props}></Icon>
