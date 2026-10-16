<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dom_6oycu.css';
import '../../css/k/k5lxwxbxz.css';
import '../../css/h/h284w7bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dom_6oycu"/><path class="k5lxwxbxz"/><path class="h284w7bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cam-20" {...props}></Icon>
