<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj7ay5b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj7ay5b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:check-all" {...props}></Icon>
