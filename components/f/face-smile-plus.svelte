<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni2qrdcan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ni2qrdcan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-smile-plus" {...props}></Icon>
