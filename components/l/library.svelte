<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t828wtvkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t828wtvkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:library" {...props}></Icon>
