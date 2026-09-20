<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slfppvv7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slfppvv7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:question-box-multiple" {...props}></Icon>
