<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojxidfsom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":962};
const content = `<path class="ojxidfsom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:favoritealt" {...props}></Icon>
