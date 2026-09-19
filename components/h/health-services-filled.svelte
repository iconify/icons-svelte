<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd6fsacyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd6fsacyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:health-services-filled" {...props}></Icon>
