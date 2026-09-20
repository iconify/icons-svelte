<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw-d8obrx.css';
import '../../css/z/zh8kziv_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw-d8obrx"/><path class="zh8kziv_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:comments-solid" {...props}></Icon>
