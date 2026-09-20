<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifnfqkh8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifnfqkh8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-up-right-solid" {...props}></Icon>
