<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_mu3rdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v3_mu3rdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:note-outline" {...props}></Icon>
