<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyuygn6di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qyuygn6di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-stored-data-duotone" {...props}></Icon>
