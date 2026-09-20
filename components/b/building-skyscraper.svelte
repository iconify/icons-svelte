<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wttt595uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wttt595uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-skyscraper" {...props}></Icon>
