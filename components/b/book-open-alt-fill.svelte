<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uitkfv-im.css';
import '../../css/n/n5mt1qbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uitkfv-im"/><path class="n5mt1qbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:book-open-alt-fill" {...props}></Icon>
