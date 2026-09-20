<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df-4nqnau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="df-4nqnau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ikuai" {...props}></Icon>
