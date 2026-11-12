<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqp834mog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dqp834mog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chitchatter-dark" {...props}></Icon>
