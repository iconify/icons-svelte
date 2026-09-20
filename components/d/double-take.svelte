<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qka7nqbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qka7nqbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:double-take" {...props}></Icon>
