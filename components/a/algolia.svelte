<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj80jg_eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj80jg_eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:algolia" {...props}></Icon>
