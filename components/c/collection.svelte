<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o86j1obkt.css';
import '../../css/s/splrb5bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o86j1obkt"/><path class="splrb5bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:collection" {...props}></Icon>
