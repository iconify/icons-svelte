<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn1teccco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hn1teccco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-tilgjengelighet-geoblocked" {...props}></Icon>
