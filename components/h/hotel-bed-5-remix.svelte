<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbldn1bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gbldn1bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:hotel-bed-5-remix" {...props}></Icon>
