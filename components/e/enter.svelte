<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzg9ekbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzg9ekbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:enter" {...props}></Icon>
