<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pamcoqbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pamcoqbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:document-x-mark" {...props}></Icon>
