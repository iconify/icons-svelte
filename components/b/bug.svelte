<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owa-ps1ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owa-ps1ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:bug" {...props}></Icon>
