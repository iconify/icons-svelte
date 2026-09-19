<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whvhgnftn.css';
import '../../css/n/nr45wil8i.css';
import '../../css/x/xi8s70b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="whvhgnftn"/><path class="nr45wil8i"/><path class="xi8s70b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:memo" {...props}></Icon>
