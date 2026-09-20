<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_ntu7akw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_ntu7akw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:folder-plus" {...props}></Icon>
