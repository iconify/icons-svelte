<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5kddqtye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5kddqtye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:list-checklist" {...props}></Icon>
