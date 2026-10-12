<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqbane7zo.css';
import '../../css/v/vuoehu_3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kqbane7zo"/><path class="vuoehu_3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-badge-stroke-20" {...props}></Icon>
