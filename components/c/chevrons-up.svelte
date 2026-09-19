<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq6etcbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq6etcbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:chevrons-up" {...props}></Icon>
