<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agbq3cbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agbq3cbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:pagelines" {...props}></Icon>
