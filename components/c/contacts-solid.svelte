<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp4gtib1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vp4gtib1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:contacts-solid" {...props}></Icon>
