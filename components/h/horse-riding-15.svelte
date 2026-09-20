<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu1ccvu1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wu1ccvu1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:horse-riding-15" {...props}></Icon>
