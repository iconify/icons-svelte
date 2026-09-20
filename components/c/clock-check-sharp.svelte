<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7q_olbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7q_olbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-check-sharp" {...props}></Icon>
