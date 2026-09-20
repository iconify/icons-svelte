<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huszaob7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="huszaob7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:nursery" {...props}></Icon>
