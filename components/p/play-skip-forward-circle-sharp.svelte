<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnoh7r61d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bnoh7r61d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:play-skip-forward-circle-sharp" {...props}></Icon>
