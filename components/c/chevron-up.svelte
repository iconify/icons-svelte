<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_awtobjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-7.5};
const content = `<path class="a_awtobjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-up" {...props}></Icon>
