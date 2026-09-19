<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/janv62ygw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="janv62ygw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:acrobat-reader" {...props}></Icon>
