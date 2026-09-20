<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cksjdsb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cksjdsb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:attribution-remix" {...props}></Icon>
