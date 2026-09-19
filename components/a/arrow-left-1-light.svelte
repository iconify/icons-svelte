<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1mivpj8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1mivpj8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-left-1-light" {...props}></Icon>
