<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqww0i2he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqww0i2he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:git-merge-x" {...props}></Icon>
