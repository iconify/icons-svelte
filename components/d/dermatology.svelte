<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ful3b6bej.css';
import '../../css/h/h5y8-bciz.css';
import '../../css/q/qqkcisb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ful3b6bej"/><path class="h5y8-bciz"/><path class="qqkcisb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:dermatology" {...props}></Icon>
