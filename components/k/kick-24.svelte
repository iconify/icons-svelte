<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvup3bmvu.css';
import '../../css/q/qt8ow3bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvup3bmvu"/><path class="qt8ow3bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:kick-24" {...props}></Icon>
