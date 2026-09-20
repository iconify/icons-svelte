<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7q-yqbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7q-yqbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:call-add-filled" {...props}></Icon>
