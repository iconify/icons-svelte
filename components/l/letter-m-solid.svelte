<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuxirh57u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuxirh57u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-m-solid" {...props}></Icon>
