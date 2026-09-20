<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py4dlzblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="py4dlzblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-left-square-filled" {...props}></Icon>
