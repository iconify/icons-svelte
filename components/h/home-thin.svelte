<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kat_4fb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kat_4fb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:home-thin" {...props}></Icon>
