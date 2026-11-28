<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugwj_abnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugwj_abnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-dots" {...props}></Icon>
