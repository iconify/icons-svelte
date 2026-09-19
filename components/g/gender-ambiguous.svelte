<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkxvn8bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wkxvn8bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:gender-ambiguous" {...props}></Icon>
