<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abn7u8b5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abn7u8b5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-line-decreasing-sharp" {...props}></Icon>
