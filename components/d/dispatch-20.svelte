<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8lb6scap.css';
import '../../css/j/j31r41azg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z8lb6scap"/><path class="j31r41azg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dispatch-20" {...props}></Icon>
