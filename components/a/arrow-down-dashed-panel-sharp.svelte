<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls-7v03zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls-7v03zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-dashed-panel-sharp" {...props}></Icon>
