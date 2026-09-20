<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsylixo6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zsylixo6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:rostrum" {...props}></Icon>
