<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npvw37byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npvw37byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:account-box-line" {...props}></Icon>
