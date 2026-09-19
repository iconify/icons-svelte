<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enctr0ztd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enctr0ztd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-1-bold" {...props}></Icon>
