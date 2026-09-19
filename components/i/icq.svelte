<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pemwhqbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="pemwhqbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:icq" {...props}></Icon>
