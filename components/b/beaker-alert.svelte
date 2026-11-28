<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lau6u465k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lau6u465k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:beaker-alert" {...props}></Icon>
