<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caiw6jbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caiw6jbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lock-keyhole" {...props}></Icon>
