<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzgf_2bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzgf_2bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-right-waves-solid" {...props}></Icon>
