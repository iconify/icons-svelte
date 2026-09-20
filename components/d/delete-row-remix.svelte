<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_-d0tb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x_-d0tb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:delete-row-remix" {...props}></Icon>
