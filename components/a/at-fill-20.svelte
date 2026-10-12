<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3tqya1df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b3tqya1df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:at-fill-20" {...props}></Icon>
