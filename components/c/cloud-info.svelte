<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpyt174ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpyt174ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-info" {...props}></Icon>
