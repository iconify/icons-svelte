<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cepev3bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cepev3bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:medium-with-circle" {...props}></Icon>
