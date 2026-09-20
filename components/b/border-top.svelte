<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5ubl_bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5ubl_bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:border-top" {...props}></Icon>
