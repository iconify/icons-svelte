<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3zir7nhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="l3zir7nhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:braillespace" {...props}></Icon>
