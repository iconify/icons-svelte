<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf-qzbccd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf-qzbccd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:libreoffice-calc" {...props}></Icon>
