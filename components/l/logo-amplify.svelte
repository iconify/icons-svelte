<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1c6wefzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n1c6wefzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-amplify" {...props}></Icon>
