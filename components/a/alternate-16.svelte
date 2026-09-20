<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk5xl6f6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hk5xl6f6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:alternate-16" {...props}></Icon>
