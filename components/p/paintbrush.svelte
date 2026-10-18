<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tplzecbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tplzecbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:paintbrush" {...props}></Icon>
