<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q04vhtbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q04vhtbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-up-right-square-solid" {...props}></Icon>
