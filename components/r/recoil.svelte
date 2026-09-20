<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbndu9beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbndu9beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:recoil" {...props}></Icon>
