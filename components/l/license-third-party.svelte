<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1sw0dbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v1sw0dbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:license-third-party" {...props}></Icon>
