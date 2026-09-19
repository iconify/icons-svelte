<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjtn75b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="kjtn75b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:newspaper" {...props}></Icon>
