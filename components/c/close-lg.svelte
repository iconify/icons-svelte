<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hot9fjbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hot9fjbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:close-lg" {...props}></Icon>
