<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqhmgi-ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqhmgi-ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:info-circle-filled" {...props}></Icon>
