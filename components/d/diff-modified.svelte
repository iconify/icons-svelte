<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4qqhxadq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4qqhxadq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:diff-modified" {...props}></Icon>
