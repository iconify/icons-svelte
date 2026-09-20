<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldszo4bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldszo4bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:directus" {...props}></Icon>
