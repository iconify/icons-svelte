<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfcglzbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfcglzbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apache-openoffice" {...props}></Icon>
