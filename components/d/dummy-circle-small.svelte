<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7ivh0b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7ivh0b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:dummy-circle-small" {...props}></Icon>
