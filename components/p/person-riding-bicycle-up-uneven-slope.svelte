<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu0j24bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bu0j24bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-riding-bicycle-up-uneven-slope" {...props}></Icon>
