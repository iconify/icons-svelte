<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jilwtdc1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jilwtdc1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-narrow-right" {...props}></Icon>
