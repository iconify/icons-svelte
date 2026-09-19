<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3ma6fbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k3ma6fbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:credit" {...props}></Icon>
