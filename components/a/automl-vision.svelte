<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz-ewac9b.css';
import '../../css/c/c-39a_bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz-ewac9b"/><path class="c-39a_bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:automl-vision" {...props}></Icon>
