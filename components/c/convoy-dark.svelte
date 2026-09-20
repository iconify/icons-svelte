<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmjc3fw5x.css';
import '../../css/d/d3p561beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hmjc3fw5x"/><path class="d3p561beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:convoy-dark" {...props}></Icon>
