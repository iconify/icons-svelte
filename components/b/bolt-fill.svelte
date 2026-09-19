<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4ldf9bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="u4ldf9bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bolt-fill" {...props}></Icon>
