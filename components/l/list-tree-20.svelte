<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acadc4zqf.css';
import '../../css/k/k9wblp0cn.css';
import '../../css/p/p4jr7vbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="acadc4zqf"/><path class="k9wblp0cn"/><path class="p4jr7vbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:list-tree-20" {...props}></Icon>
