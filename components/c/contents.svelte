<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaj_zwtys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yaj_zwtys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:contents" {...props}></Icon>
