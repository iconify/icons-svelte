<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms2gyg5jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms2gyg5jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:anydesk" {...props}></Icon>
