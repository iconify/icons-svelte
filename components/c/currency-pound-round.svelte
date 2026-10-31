<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esu9gttcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esu9gttcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-pound-round" {...props}></Icon>
