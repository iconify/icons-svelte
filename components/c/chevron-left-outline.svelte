<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isns3yuhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isns3yuhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:chevron-left-outline" {...props}></Icon>
