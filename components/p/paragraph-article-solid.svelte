<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn7fs3i6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pn7fs3i6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:paragraph-article-solid" {...props}></Icon>
