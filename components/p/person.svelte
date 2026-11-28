<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blbfuxb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blbfuxb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:person" {...props}></Icon>
