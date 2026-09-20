<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j79n9n5fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j79n9n5fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:list-check-solid" {...props}></Icon>
