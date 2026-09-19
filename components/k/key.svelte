<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9fxnqbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1696,"height":1600};
const content = `<path class="n9fxnqbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:key" {...props}></Icon>
