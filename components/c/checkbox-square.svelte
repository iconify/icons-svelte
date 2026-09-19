<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af1k-_boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af1k-_boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:checkbox-square" {...props}></Icon>
