<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcu8gub2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rcu8gub2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:caret-back-circle-sharp" {...props}></Icon>
