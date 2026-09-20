<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_f6zsgma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_f6zsgma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:definition-search-book" {...props}></Icon>
