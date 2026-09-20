<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltam8gb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ltam8gb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:article-search" {...props}></Icon>
