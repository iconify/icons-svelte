<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drqqs-5cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="drqqs-5cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:litecoin-circle-solid" {...props}></Icon>
