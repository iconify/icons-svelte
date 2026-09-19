<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjxv15xvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wjxv15xvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-model-s" {...props}></Icon>
