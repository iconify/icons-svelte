<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csji57hci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="csji57hci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:add-alarm-fill" {...props}></Icon>
