<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay2pkabdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ay2pkabdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-tilgjengelighet-ikkelengertilgjengelig" {...props}></Icon>
