<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h120-nbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h120-nbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:instapods-dark" {...props}></Icon>
