<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5v5k58ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t5v5k58ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-pencil-fill-20" {...props}></Icon>
