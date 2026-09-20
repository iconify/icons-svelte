<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqa_88bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqa_88bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-neutral" {...props}></Icon>
