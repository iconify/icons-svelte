<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9a2cqbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h9a2cqbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-archive" {...props}></Icon>
