<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9bnb65oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9bnb65oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:align-vertically" {...props}></Icon>
