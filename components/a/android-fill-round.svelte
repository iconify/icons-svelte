<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trqwz6wjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trqwz6wjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:android-fill-round" {...props}></Icon>
