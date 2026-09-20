<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsnmh2bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zsnmh2bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:open-umbrella-remix" {...props}></Icon>
