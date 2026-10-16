<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbu76sy7z.css';
import '../../css/n/nr2v8obrq.css';
import '../../css/b/b-1ddne5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lbu76sy7z"/><path class="nr2v8obrq"/><path class="b-1ddne5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:assembly-line-20-bold" {...props}></Icon>
