<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g77a37bgg.css';
import '../../css/u/ur3w_zb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g77a37bgg"/><path class="ur3w_zb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nicotine-plus-light" {...props}></Icon>
