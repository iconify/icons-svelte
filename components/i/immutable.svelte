<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1h1vs9it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1h1vs9it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:immutable" {...props}></Icon>
