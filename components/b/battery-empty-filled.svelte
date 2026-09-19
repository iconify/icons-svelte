<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssrlkj0dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssrlkj0dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:battery-empty-filled" {...props}></Icon>
