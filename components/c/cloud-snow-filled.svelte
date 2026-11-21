<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ary60mj0w.css';
import '../../css/f/fk-8gjbyw.css';
import '../../css/j/j14em3y7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ary60mj0w"/><path class="fk-8gjbyw"/><path class="j14em3y7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-snow-filled" {...props}></Icon>
