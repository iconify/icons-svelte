<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egmj6edzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="egmj6edzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-film" {...props}></Icon>
