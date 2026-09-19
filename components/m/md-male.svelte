<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quhl277kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="quhl277kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-male" {...props}></Icon>
