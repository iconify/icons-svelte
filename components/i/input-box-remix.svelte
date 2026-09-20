<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je9cy9swr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="je9cy9swr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:input-box-remix" {...props}></Icon>
