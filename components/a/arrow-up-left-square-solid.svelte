<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs6uoeyib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs6uoeyib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-up-left-square-solid" {...props}></Icon>
