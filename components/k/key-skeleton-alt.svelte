<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1ud49bhs.css';
import '../../css/z/zhvsnqbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1ud49bhs"/><path class="zhvsnqbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:key-skeleton-alt" {...props}></Icon>
