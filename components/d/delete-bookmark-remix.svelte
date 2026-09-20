<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smmizc_-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="smmizc_-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:delete-bookmark-remix" {...props}></Icon>
