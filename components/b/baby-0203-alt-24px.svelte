<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtk5vsb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtk5vsb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:baby-0203-alt-24px" {...props}></Icon>
