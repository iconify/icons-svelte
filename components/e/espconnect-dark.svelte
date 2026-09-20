<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etg9crbrk.css';
import '../../css/x/x2l7nqbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="etg9crbrk"/><path class="x2l7nqbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:espconnect-dark" {...props}></Icon>
