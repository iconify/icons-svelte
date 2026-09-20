<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfk5gh6or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfk5gh6or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:parcel" {...props}></Icon>
