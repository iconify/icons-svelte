<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkwxxqb3q.css';
import '../../css/n/n9oq2eb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kkwxxqb3q"/><path class="n9oq2eb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cobalt-20-bold" {...props}></Icon>
