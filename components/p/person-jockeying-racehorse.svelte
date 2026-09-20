<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l20rk1brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l20rk1brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-jockeying-racehorse" {...props}></Icon>
